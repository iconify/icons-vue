<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wv797gbzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wv797gbzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:lifebuoy" /></template>
