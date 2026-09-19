<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dnk44odyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dnk44odyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:chevron-up" /></template>
