<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t0siyqbzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="t0siyqbzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrow-uturn-left-square" /></template>
