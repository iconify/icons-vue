<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uzkebvbwp.css';
import '../../css/h/h3qchvbhn.css';
import '../../css/u/uw1uypbnt.css';
import '../../css/o/o9dpakbzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<rect class="uzkebvbwp"/><rect class="h3qchvbhn"/><rect class="uw1uypbnt"/><rect class="o9dpakbzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:cellular-outline" /></template>
