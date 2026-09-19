<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/td2qqkb6u.css';
import '../../css/w/w6198jjkw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="td2qqkb6u"/><path class="w6198jjkw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-barcode-reader" /></template>
