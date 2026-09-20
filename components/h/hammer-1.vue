<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a2p1d0b1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="a2p1d0b1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:hammer-1" /></template>
