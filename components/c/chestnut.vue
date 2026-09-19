<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vhz5i4bfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="vhz5i4bfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:chestnut" /></template>
