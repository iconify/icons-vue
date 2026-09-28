<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xrmyc0byc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="xrmyc0byc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:cartoon-cannon" /></template>
