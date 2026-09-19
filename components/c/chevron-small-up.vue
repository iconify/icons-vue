<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_9plbb5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="o_9plbb5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:chevron-small-up" /></template>
