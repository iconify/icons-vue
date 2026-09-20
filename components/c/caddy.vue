<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x299ovbev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x299ovbev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:caddy" /></template>
