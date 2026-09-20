<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/glvt67bak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="glvt67bak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:bitcoin-circle" /></template>
