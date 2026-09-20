<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/utzkmlbli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="utzkmlbli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:aptabase-light" /></template>
