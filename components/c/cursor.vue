<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-q-q20kk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":642,"height":1024};
const content = `<path class="k-q-q20kk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:cursor" /></template>
