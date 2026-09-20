<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqs-klmvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qqs-klmvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:beaver-habit-tracker-light" /></template>
