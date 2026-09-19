<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b90k02bgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":768};
const content = `<path class="b90k02bgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:alignverticalcenter" /></template>
