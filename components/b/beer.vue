<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ug7jhnban.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ug7jhnban"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:beer" /></template>
