<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v6zd-wqxa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="v6zd-wqxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:asterisk-1-flat" /></template>
