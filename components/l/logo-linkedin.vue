<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ngcs7cb3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="ngcs7cb3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:logo-linkedin" /></template>
