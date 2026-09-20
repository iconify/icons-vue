<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zna8a2b9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zna8a2b9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:floppy-variant" /></template>
