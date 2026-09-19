<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zoulf5bes.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zoulf5bes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:logo-alipay" /></template>
