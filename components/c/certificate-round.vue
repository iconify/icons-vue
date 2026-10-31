<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cdy_6m8-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cdy_6m8-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:certificate-round" /></template>
