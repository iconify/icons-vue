<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dq89kpweo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dq89kpweo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:dharmachakra-solid" /></template>
