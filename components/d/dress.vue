<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ie0os72rp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ie0os72rp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:dress" /></template>
