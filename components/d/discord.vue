<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzzpj9b5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pzzpj9b5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:discord" /></template>
