<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wn5ia6wrr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":504};
const content = `<path class="wn5ia6wrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:cpu" /></template>
