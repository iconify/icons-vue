<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qr8yrusdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qr8yrusdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:clapperboard-open-outline" /></template>
