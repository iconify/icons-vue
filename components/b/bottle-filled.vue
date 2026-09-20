<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gufolm2bk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gufolm2bk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bottle-filled" /></template>
