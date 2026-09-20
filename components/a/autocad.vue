<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wvum6ki5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wvum6ki5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:autocad" /></template>
