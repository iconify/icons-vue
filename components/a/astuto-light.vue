<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ak69pm-aa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ak69pm-aa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:astuto-light" /></template>
