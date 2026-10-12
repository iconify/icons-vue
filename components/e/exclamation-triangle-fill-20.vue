<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nc5vh_0ib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nc5vh_0ib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:exclamation-triangle-fill-20" /></template>
