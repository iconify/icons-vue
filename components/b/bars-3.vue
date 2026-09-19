<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kng6abcjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kng6abcjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:bars-3" /></template>
