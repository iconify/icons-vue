<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/km2deyk9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="km2deyk9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:divider-1" /></template>
