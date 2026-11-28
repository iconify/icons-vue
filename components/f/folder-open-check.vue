<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2m2r2hpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d2m2r2hpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:folder-open-check" /></template>
