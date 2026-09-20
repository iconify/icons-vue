<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vu11w07_v.css';
import '../../css/f/f0yad6-af.css';
import '../../css/c/cq_2o7u8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vu11w07_v"/><path class="f0yad6-af"/><path clip-rule="evenodd" class="cq_2o7u8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bone-broken-outline" /></template>
