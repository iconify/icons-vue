<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nm2hqdbxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nm2hqdbxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:church-solid" /></template>
