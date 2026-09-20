<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whix8lsva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="whix8lsva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:british-airways" /></template>
