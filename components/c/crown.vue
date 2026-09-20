<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ue8808q3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ue8808q3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:crown" /></template>
