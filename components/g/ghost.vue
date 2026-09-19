<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zr6shkb4z.css';
import '../../css/p/p11_xsbtc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zr6shkb4z"/><path class="p11_xsbtc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:ghost" /></template>
