<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hj0bo8wrk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hj0bo8wrk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:keyboard" /></template>
