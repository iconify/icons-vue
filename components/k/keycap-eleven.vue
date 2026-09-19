<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1ha_-7me.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="m1ha_-7me"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:keycap-eleven" /></template>
