<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/soj2p2bnn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1023};
const content = `<path class="soj2p2bnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:fork" /></template>
