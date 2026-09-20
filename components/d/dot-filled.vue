<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w3p6w_dsx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="w3p6w_dsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:dot-filled" /></template>
