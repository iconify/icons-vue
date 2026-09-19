<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y6rceob1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="y6rceob1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:eight-of-bamboos-mahjong" /></template>
