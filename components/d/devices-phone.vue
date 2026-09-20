<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vz464s1hv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="vz464s1hv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:devices-phone" /></template>
