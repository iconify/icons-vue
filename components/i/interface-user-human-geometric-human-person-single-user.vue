<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cyhzczbpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="cyhzczbpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-user-human-geometric-human-person-single-user" /></template>
