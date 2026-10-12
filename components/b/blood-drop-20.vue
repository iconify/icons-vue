<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_vodpr_t.css';
import '../../css/z/z0mp7-b9d.css';
import '../../css/l/l724hebta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="z_vodpr_t"/><path class="z0mp7-b9d"/><path class="l724hebta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:blood-drop-20" /></template>
