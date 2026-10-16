<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mytv6xbyl.css';
import '../../css/v/va8q5vg9j.css';
import '../../css/y/y8j-xvbmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mytv6xbyl"/><path class="va8q5vg9j"/><path class="y8j-xvbmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:greenhouse-48" /></template>
