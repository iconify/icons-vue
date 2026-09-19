<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qv7pv6b9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qv7pv6b9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:aircraft-take-off" /></template>
