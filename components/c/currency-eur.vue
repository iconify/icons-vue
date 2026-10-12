<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/invhf0-gq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="invhf0-gq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:currency-eur" /></template>
