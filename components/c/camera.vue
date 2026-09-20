<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hlht_y30p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hlht_y30p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:camera" /></template>
