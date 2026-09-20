<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x200m4bhu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x200m4bhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:arrow-right-expressive" /></template>
