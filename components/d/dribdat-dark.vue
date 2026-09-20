<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ah7r5tboe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ah7r5tboe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dribdat-dark" /></template>
