<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b6erbx_3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b6erbx_3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:finger-rock-fill" /></template>
