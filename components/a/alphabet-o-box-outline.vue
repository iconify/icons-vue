<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lcf4q5osf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lcf4q5osf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:alphabet-o-box-outline" /></template>
