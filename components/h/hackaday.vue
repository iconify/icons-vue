<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pnj5y5did.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pnj5y5did"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:hackaday" /></template>
