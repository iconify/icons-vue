<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udwsy0bof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="udwsy0bof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:dice4" /></template>
