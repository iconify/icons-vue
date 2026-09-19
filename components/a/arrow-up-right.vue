<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2r8b5pqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d2r8b5pqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:arrow-up-right" /></template>
