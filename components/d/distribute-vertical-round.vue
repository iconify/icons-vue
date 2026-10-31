<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lk73n3bfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lk73n3bfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:distribute-vertical-round" /></template>
