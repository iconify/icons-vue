<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yox3j-b4i.css';
import '../../css/i/ivt8o-bva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yox3j-b4i"/><path class="ivt8o-bva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:book" /></template>
