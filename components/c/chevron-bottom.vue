<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p06umcb4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p06umcb4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:chevron-bottom" /></template>
