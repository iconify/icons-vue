<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3z1tdgxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="u3z1tdgxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:credit-card-20-solid" /></template>
