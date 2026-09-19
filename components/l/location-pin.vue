<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yyatedb_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="yyatedb_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:location-pin" /></template>
