<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bknck_d4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bknck_d4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:keras" /></template>
