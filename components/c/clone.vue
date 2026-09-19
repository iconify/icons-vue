<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g2999fbld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g2999fbld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:clone" /></template>
