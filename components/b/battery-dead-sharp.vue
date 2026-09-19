<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qge0pjb9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qge0pjb9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:battery-dead-sharp" /></template>
