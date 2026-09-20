<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9y9f9u5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u9y9f9u5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:archive-star" /></template>
