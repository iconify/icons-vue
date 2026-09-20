<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ps9736b1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ps9736b1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:fujitsu" /></template>
