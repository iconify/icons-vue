<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o5r3k3vyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="o5r3k3vyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:compass" /></template>
