<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wyle9lbps.css';
import '../../css/a/amvusujsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wyle9lbps"/><path clip-rule="evenodd" class="amvusujsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:cnht" /></template>
