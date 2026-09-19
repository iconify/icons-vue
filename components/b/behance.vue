<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gy4-pm1pa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gy4-pm1pa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo-social:behance" /></template>
