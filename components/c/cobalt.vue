<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ybz7xp5wk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ybz7xp5wk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:cobalt" /></template>
