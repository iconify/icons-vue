<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nqkpo4bpk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nqkpo4bpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:dots-three-vertical" /></template>
