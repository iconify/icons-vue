<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qzjf97_aw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qzjf97_aw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:feather" /></template>
