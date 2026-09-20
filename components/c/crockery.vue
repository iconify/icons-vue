<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yzlcb_btt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yzlcb_btt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:crockery" /></template>
