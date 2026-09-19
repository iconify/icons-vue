<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dn18l3rik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dn18l3rik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:hive" /></template>
