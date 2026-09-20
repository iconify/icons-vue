<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sx3aksgyw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sx3aksgyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:linkedin-dark" /></template>
