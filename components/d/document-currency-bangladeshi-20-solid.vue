<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ukf_7svqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="ukf_7svqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:document-currency-bangladeshi-20-solid" /></template>
