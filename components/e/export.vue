<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lnlw47_jg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lnlw47_jg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:export" /></template>
