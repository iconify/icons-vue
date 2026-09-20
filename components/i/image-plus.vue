<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k4j-itpzn.css';
import '../../css/w/wch9wu0eu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k4j-itpzn"/><path class="wch9wu0eu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:image-plus" /></template>
