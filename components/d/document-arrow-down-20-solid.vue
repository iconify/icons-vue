<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qus7vzb2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="qus7vzb2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:document-arrow-down-20-solid" /></template>
