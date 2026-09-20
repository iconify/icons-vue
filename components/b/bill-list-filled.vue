<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn1i5feok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xn1i5feok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:bill-list-filled" /></template>
