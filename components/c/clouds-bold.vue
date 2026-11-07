<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ewaos-x_y.css';
import '../../css/p/p2vfxjbvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ewaos-x_y"/><path class="p2vfxjbvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:clouds-bold" /></template>
