<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f02kcfcvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f02kcfcvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:caret-right-circle" /></template>
