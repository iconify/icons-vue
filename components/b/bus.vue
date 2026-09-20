<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/plh1jrbcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="plh1jrbcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:bus" /></template>
