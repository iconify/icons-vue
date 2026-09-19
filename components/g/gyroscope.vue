<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rs6jf3bos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="rs6jf3bos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:gyroscope" /></template>
