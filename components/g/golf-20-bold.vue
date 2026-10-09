<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lwpjg0bhd.css';
import '../../css/c/c_dqrlbfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lwpjg0bhd"/><path class="c_dqrlbfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:golf-20-bold" /></template>
