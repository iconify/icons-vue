<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xac5i9bpe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xac5i9bpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:invoice-filled" /></template>
