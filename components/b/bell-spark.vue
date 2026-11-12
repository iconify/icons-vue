<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xqhdt28zg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xqhdt28zg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bell-spark" /></template>
