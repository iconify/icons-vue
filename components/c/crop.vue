<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pckrh5b6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="pckrh5b6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:crop" /></template>
