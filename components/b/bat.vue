<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ilpg2j-hn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ilpg2j-hn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:bat" /></template>
