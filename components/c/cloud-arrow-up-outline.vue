<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eg7rm06cd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eg7rm06cd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cloud-arrow-up-outline" /></template>
