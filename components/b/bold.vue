<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yi2j6qb-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="yi2j6qb-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:bold" /></template>
