<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ji9nld9gb.css';
import '../../css/r/rg45w14ll.css';
import '../../css/v/vi504dbkq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ji9nld9gb"/><path class="rg45w14ll"/><path class="vi504dbkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:fingerprint-filled" /></template>
