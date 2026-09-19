<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v439n2bfl.css';
import '../../css/d/dcra57g9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v439n2bfl"/><path class="dcra57g9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-tennis-ball" /></template>
