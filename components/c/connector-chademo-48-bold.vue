<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q668lybvz.css';
import '../../css/m/mmf760o5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q668lybvz"/><path class="mmf760o5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:connector-chademo-48-bold" /></template>
