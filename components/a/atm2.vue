<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hbch_7bfy.css';
import '../../css/y/y9fzgxb1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hbch_7bfy"/><path class="y9fzgxb1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:atm2" /></template>
