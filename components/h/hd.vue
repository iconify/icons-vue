<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hm1xjabun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hm1xjabun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:hd" /></template>
