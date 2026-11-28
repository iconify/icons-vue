<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sl-t0bawj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sl-t0bawj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:image-off" /></template>
