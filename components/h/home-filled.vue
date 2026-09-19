<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zbwic474o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zbwic474o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:home-filled" /></template>
