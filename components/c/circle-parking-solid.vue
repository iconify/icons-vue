<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oee2xac1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oee2xac1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:circle-parking-solid" /></template>
