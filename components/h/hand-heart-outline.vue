<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbxtqyw3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kbxtqyw3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:hand-heart-outline" /></template>
