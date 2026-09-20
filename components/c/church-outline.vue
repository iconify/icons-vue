<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zx6kp1g_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zx6kp1g_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:church-outline" /></template>
