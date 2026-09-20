<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mmznuabvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mmznuabvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:diun-dash-dark" /></template>
