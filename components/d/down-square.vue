<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xouoj826l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xouoj826l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:down-square" /></template>
