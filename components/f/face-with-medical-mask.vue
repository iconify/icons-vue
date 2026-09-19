<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9zkttbmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="s9zkttbmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:face-with-medical-mask" /></template>
