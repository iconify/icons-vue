<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o86ll_bsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o86ll_bsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:emoticon-kiss" /></template>
