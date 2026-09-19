<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_82urleq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="s_82urleq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:chevron-small-left" /></template>
