<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pyb6gkxed.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pyb6gkxed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:columns-3" /></template>
