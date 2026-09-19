<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nh88sjbzq.css';
import '../../css/n/nhpgwyiio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nh88sjbzq"/><path class="nhpgwyiio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:dog-body" /></template>
