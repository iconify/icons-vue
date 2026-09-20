<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hs4emibqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="hs4emibqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:element" /></template>
