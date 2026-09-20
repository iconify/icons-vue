<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z8vaz6bvv.css';
import '../../css/p/pn6ejhb8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z8vaz6bvv"/><path class="pn6ejhb8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:discount-filled" /></template>
