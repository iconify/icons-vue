<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xkacrgbkn.css';
import '../../css/f/fhr0udsbr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xkacrgbkn"/><path class="fhr0udsbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:cluster-management" /></template>
