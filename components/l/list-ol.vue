<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kb2thqbgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kb2thqbgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:list-ol" /></template>
