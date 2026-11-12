<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hw30mccjj.css';
import '../../css/w/w-fm7jz3a.css';
import '../../css/i/idx93qbfz.css';
import '../../css/c/cf9gd76rf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hw30mccjj"/><circle class="w-fm7jz3a"/><path class="idx93qbfz"/><path class="cf9gd76rf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cloudreve-light" /></template>
