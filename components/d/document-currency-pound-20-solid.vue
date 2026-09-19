<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cqn1lpbcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="cqn1lpbcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:document-currency-pound-20-solid" /></template>
