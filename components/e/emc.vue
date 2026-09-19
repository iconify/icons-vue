<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwwnof78l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bwwnof78l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:emc" /></template>
