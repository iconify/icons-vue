<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zgwpwkbxm.css';
import '../../css/l/lz5trxqpe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zgwpwkbxm"/><path class="lz5trxqpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:language-outline" /></template>
