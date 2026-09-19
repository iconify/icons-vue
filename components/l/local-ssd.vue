<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8m4jds0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s8m4jds0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gcp:local-ssd" /></template>
