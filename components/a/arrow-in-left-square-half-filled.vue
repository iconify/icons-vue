<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ooaqbg7av.css';
import '../../css/l/l3bwhaczb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ooaqbg7av"/><path class="l3bwhaczb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-in-left-square-half-filled" /></template>
