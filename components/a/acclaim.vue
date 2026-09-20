<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rdlufvbeq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="rdlufvbeq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:acclaim" /></template>
