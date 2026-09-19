<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbvbhzfuv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bbvbhzfuv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:link-out" /></template>
