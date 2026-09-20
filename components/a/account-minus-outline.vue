<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f777k-bdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f777k-bdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:account-minus-outline" /></template>
