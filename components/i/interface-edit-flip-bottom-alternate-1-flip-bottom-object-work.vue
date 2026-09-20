<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v02yasbok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="v02yasbok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-edit-flip-bottom-alternate-1-flip-bottom-object-work" /></template>
