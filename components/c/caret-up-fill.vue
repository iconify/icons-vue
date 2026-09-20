<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dum4ig9bs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dum4ig9bs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:caret-up-fill" /></template>
