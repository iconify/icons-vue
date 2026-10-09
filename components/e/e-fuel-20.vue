<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gwh1q-fzk.css';
import '../../css/o/okro7rlip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gwh1q-fzk"/><path class="okro7rlip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:e-fuel-20" /></template>
