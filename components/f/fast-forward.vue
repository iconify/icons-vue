<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-2r3ac9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l-2r3ac9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:fast-forward" /></template>
