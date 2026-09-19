<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/epm3pib-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="epm3pib-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:backspace-20-solid" /></template>
