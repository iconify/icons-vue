<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2ei2acct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="i2ei2acct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:clock-plus-thin" /></template>
