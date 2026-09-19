<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u5yqucbgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":480,"height":512};
const content = `<path class="u5yqucbgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:dependabot" /></template>
