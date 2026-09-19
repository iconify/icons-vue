<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjw4yqthe.css';
import '../../css/y/ylop8ebio.css';
import '../../css/s/s0fwv-0ek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sjw4yqthe"/><path class="ylop8ebio"/><path class="s0fwv-0ek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gcp:gke-on-prem" /></template>
