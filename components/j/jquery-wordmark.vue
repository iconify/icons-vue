<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xk77iabep.css';
import '../../css/i/it3-pwbqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="xk77iabep"/><path class="it3-pwbqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:jquery-wordmark" /></template>
