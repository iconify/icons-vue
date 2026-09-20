<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/itmohpb2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="itmohpb2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:geode" /></template>
