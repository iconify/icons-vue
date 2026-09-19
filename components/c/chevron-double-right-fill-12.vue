<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nnzxjem_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="nnzxjem_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:chevron-double-right-fill-12" /></template>
