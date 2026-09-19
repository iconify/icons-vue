<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pft_zib7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="pft_zib7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:doc" /></template>
