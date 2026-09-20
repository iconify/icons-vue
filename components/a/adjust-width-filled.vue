<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pw98_2wjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="pw98_2wjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:adjust-width-filled" /></template>
