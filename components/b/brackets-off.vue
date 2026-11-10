<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wirrzg--d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wirrzg--d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:brackets-off" /></template>
