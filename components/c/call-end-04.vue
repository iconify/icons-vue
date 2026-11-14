<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-jf2nb1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t-jf2nb1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:call-end-04" /></template>
