<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w6twikypo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="w6twikypo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:calendar-solid" /></template>
