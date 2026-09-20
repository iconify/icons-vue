<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s5v1l59cj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s5v1l59cj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:arrow-upward-duotone" /></template>
