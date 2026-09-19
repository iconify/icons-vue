<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cbb_tgbii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cbb_tgbii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:inbox" /></template>
