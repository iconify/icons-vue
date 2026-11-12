<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8-9ihkig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g8-9ihkig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:itsm-ng" /></template>
