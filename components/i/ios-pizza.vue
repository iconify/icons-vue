<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/inq66m2pg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="inq66m2pg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-pizza" /></template>
