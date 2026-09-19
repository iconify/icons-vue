<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l2l086bip.css';
import '../../css/i/iqk83abwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l2l086bip"/><path class="iqk83abwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:egg-fried" /></template>
