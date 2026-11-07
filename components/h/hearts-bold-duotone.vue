<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o0qokrk2d.css';
import '../../css/h/h4x0vob4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o0qokrk2d"/><path class="h4x0vob4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:hearts-bold-duotone" /></template>
