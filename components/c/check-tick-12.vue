<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/moxwz9eot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="moxwz9eot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:check-tick-12" /></template>
