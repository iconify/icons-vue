<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y22f7pbxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="y22f7pbxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:circle-with-plus" /></template>
