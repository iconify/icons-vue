<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fx8vj2brj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="fx8vj2brj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:ladder" /></template>
