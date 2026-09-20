<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kq3m-xb3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kq3m-xb3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kbin-light" /></template>
