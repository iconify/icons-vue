<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jyqwv_kza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jyqwv_kza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cilium-dark" /></template>
