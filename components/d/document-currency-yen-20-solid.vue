<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6ij-rbll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="d6ij-rbll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:document-currency-yen-20-solid" /></template>
