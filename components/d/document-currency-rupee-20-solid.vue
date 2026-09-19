<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l5zexx5pd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="l5zexx5pd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:document-currency-rupee-20-solid" /></template>
