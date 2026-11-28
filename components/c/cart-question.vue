<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dbmsg7kfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dbmsg7kfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:cart-question" /></template>
