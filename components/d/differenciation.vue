<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uto8vj0dn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":14};
const content = `<path class="uto8vj0dn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:differenciation" /></template>
