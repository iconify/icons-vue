<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uzv93wbnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uzv93wbnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:bewcloud-light" /></template>
