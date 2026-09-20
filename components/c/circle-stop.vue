<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gic3z1hlp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gic3z1hlp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:circle-stop" /></template>
