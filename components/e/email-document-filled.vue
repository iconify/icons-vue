<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xt01scb7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="xt01scb7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:email-document-filled" /></template>
