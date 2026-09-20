<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dqnsdnbcn.css';
import '../../css/n/n47uc4bkd.css';
import '../../css/u/ukoujx6ly.css';
import '../../css/y/y1ar7-bhy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dqnsdnbcn"/><path class="n47uc4bkd"/><path class="ukoujx6ly"/><path class="y1ar7-bhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-emojis:crescent-moon" /></template>
