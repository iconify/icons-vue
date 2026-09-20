<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vhhqttbfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vhhqttbfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:lufin-light" /></template>
