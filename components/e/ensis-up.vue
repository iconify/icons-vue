<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ib_exgb_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ib_exgb_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ensis-up" /></template>
