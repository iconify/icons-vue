<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dv6y-3b6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="dv6y-3b6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:android" /></template>
