<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vinqr1xim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vinqr1xim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:five-star-badge" /></template>
