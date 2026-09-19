<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7s6tsbkb.css';
import '../../css/d/d7vyowb-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l7s6tsbkb"/><path class="d7vyowb-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:close-square-outline" /></template>
