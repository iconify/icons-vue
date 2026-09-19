<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yb3cn3bcv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="yb3cn3bcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:asterisk-circle-fill" /></template>
