<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-brn9h0g.css';
import '../../css/k/kceoj0bsx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x-brn9h0g"/><path class="kceoj0bsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:centos-light" /></template>
