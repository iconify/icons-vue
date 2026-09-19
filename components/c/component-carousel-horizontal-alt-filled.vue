<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bel73sblq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bel73sblq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:component-carousel-horizontal-alt-filled" /></template>
