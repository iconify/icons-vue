<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xcxxl1c-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xcxxl1c-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:invio" /></template>
