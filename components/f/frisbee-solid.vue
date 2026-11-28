<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/znuu2hcur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="znuu2hcur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:frisbee-solid" /></template>
