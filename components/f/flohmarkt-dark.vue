<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uv28m5ido.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uv28m5ido"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:flohmarkt-dark" /></template>
