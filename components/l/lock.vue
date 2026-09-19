<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bk_ksfbpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":560,"height":840};
const content = `<path class="bk_ksfbpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="il:lock" /></template>
