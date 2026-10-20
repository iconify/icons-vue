<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a969tno5c.css';
import '../../css/j/j4abbg0tt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="a969tno5c"/><path class="j4abbg0tt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:binoculars-20-bold" /></template>
