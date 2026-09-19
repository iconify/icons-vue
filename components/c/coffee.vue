<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7jhd1bei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":448};
const content = `<path class="s7jhd1bei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:coffee" /></template>
