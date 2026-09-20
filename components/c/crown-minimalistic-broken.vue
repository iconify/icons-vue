<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6kaugbvt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g6kaugbvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:crown-minimalistic-broken" /></template>
