<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rbnll0bho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rbnll0bho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:lock-star" /></template>
