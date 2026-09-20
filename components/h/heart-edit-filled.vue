<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iht6htblh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iht6htblh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:heart-edit-filled" /></template>
