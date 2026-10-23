<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/li3m1bnbg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="li3m1bnbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:barrel" /></template>
