<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d4h742bvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d4h742bvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:bagisto-dark" /></template>
