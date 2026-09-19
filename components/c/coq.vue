<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ky3unnbnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":342,"height":512};
const content = `<path class="ky3unnbnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:coq" /></template>
