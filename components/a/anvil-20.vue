<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oako69bqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="oako69bqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:anvil-20" /></template>
