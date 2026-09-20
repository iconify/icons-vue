<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hp847_bcm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hp847_bcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:audiomack" /></template>
