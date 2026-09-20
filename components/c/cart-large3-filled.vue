<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/prqma6b6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="prqma6b6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:cart-large3-filled" /></template>
