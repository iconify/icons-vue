<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zpa83o-uf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zpa83o-uf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:logo-tdesign-filled" /></template>
