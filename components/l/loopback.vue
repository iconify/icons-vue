<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-tn9nbkk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r-tn9nbkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:loopback" /></template>
