<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nnr3be0jq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nnr3be0jq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:codeflicker" /></template>
