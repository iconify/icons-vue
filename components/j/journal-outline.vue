<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vyolq2bek.css';
import '../../css/c/c_71ubcpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<rect class="vyolq2bek"/><path class="c_71ubcpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:journal-outline" /></template>
