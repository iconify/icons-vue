<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zf0olab_z.css';
import '../../css/e/ejx2y1bzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zf0olab_z"/><path class="ejx2y1bzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cloud-storm-bold-duotone" /></template>
