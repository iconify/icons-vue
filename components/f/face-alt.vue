<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qilianfni.css';
import '../../css/b/bv-ewi9vo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qilianfni"/><path class="bv-ewi9vo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:face-alt" /></template>
