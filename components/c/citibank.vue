<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nttp5bcbi.css';
import '../../css/u/uzxqaob3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nttp5bcbi"/><path class="uzxqaob3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:citibank" /></template>
