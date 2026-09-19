<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jzploib2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="jzploib2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:currency-euro-20-solid" /></template>
