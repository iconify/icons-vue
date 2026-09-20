<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tbhxgubwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tbhxgubwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:bookingdotcom" /></template>
