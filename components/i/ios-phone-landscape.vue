<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cfg-xccrw.css';
import '../../css/q/qo397l2vm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cfg-xccrw"/><path class="qo397l2vm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-phone-landscape" /></template>
