<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aqr4zbbdb.css';
import '../../css/k/kmp8rebtm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aqr4zbbdb"/><path class="kmp8rebtm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:coin-b-fill" /></template>
