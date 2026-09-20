<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wr_827brv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wr_827brv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:caret-right-solid" /></template>
