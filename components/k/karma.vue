<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ns5-s36pk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ns5-s36pk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:karma" /></template>
