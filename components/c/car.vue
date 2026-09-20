<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2wbqwbqv.css';
import '../../css/t/t4exnpses.css';
import '../../css/j/jzjyesbzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i2wbqwbqv"/><circle class="t4exnpses"/><circle class="jzjyesbzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:car" /></template>
