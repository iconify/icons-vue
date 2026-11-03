<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zfeohs2bk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zfeohs2bk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kept-inventory-dark" /></template>
