<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sn6wamb3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sn6wamb3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:link" /></template>
