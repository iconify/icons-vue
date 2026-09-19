<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ze28hzlyg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ze28hzlyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:keycap-digit-three-filled" /></template>
