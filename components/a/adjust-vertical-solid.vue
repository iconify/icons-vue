<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h7q6txb3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="h7q6txb3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:adjust-vertical-solid" /></template>
