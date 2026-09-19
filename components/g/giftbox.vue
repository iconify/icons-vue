<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zfcvn_bpk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="zfcvn_bpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:giftbox" /></template>
