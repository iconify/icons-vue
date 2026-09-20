<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pht-9fylt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pht-9fylt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:eye-slash" /></template>
