<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/o/ouvmfj4ut.css';
import '../../css/b/bomz11bhc.css';
import '../../css/b/buo1kubox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ouvmfj4ut"/><path class="bomz11bhc"/><path class="buo1kubox"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bag-smile-broken" /></template>
