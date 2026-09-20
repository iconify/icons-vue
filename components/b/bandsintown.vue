<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fg6y7tbvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fg6y7tbvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:bandsintown" /></template>
