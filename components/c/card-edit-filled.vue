<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/efk22ccyi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="efk22ccyi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:card-edit-filled" /></template>
