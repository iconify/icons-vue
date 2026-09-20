<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k1nvh3bro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="k1nvh3bro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:leaf-above-outstretched-hand" /></template>
