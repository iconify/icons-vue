<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4i1geb6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f4i1geb6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:channel-4-uk" /></template>
