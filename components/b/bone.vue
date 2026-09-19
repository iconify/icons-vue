<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtuj_swat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="jtuj_swat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:bone" /></template>
