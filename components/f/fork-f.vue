<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_xli40hk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-4,"top":-1.5};
const content = `<path class="w_xli40hk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:fork-f" /></template>
