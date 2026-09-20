<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kw2nd2ben.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kw2nd2ben"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:hand-wash-outline" /></template>
