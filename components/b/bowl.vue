<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p5o00ib2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p5o00ib2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bowl" /></template>
