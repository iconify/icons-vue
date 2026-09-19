<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oh9871bfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oh9871bfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:globe-alt-filled" /></template>
