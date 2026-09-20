<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1ia8ya8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c1ia8ya8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:key-round" /></template>
