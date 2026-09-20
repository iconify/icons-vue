<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zgamo4zls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zgamo4zls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:development-containers" /></template>
