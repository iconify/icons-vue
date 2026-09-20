<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cdfbt-bcx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cdfbt-bcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:check" /></template>
