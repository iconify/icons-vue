<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ae5cuqhku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ae5cuqhku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:arrow-long-down" /></template>
