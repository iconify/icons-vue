<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/as6eg0b3o.css';
import '../../css/i/i7sr6ubzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="as6eg0b3o"/><path class="i7sr6ubzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:check-list-solid" /></template>
