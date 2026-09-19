<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-bbnvbzg.css';
import '../../css/m/mvcw08bgw.css';
import '../../css/a/akdbaebrb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l-bbnvbzg"/><path class="mvcw08bgw"/><path class="akdbaebrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:layers-filled" /></template>
