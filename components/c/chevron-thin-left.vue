<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vb785qb9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vb785qb9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:chevron-thin-left" /></template>
