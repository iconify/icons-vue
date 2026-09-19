<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w--sykbuv.css';
import '../../css/i/ik2-15cxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w--sykbuv"/><path class="ik2-15cxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:behance-fill" /></template>
