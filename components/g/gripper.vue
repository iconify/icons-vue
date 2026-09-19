<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z1gfipb9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="z1gfipb9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:gripper" /></template>
