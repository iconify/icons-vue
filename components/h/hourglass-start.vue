<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ip6mpoouv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ip6mpoouv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:hourglass-start" /></template>
