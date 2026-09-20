<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zscdv2etd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zscdv2etd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:compass-outline" /></template>
