<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dmg3osppk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dmg3osppk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:fridge-alert" /></template>
