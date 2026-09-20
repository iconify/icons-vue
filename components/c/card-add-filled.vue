<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vjeghq10v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vjeghq10v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:card-add-filled" /></template>
