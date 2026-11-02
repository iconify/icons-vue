<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_y8nv_ip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r_y8nv_ip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bookmark-edit-line" /></template>
