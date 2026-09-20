<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ug10fabmp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ug10fabmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:audio-lines-search-fill" /></template>
