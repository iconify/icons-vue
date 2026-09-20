<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhzv6bmss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rhzv6bmss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:corona-renderer" /></template>
