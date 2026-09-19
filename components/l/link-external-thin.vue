<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l42-2yu0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l42-2yu0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:link-external-thin" /></template>
