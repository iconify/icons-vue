<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/knjmtjbyd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="knjmtjbyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:fedex-dark" /></template>
