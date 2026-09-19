<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zx_s6bg8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zx_s6bg8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:bbc-world-service" /></template>
