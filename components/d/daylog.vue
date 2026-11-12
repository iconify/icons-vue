<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udzhtcbgx.css';
import '../../css/b/bneojtbom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="udzhtcbgx"/><path class="bneojtbom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:daylog" /></template>
