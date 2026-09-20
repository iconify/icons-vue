<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lnbv4uh6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lnbv4uh6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:content-save-off" /></template>
