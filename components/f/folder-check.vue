<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ad9e7wz3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ad9e7wz3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:folder-check" /></template>
