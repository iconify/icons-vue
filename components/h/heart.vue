<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ie-0hme5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ie-0hme5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:heart" /></template>
