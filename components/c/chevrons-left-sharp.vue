<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wi1rvacfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wi1rvacfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chevrons-left-sharp" /></template>
