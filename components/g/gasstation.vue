<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nu0a__bhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1023};
const content = `<path class="nu0a__bhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:gasstation" /></template>
