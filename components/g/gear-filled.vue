<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofbirtxga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ofbirtxga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:gear-filled" /></template>
