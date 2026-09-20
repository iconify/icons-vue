<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ns1pa3bol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="ns1pa3bol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-edit-flip-up-design-up-flip-reflect-vertical" /></template>
