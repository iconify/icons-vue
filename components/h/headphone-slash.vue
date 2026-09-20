<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7xw74zlj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u7xw74zlj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:headphone-slash" /></template>
