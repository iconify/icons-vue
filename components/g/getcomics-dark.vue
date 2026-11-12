<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t5zt96c_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t5zt96c_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:getcomics-dark" /></template>
