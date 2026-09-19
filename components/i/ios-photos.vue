<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bfrw229ma.css';
import '../../css/y/yz4sh9bvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bfrw229ma"/><path class="yz4sh9bvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-photos" /></template>
