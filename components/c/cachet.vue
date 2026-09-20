<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mf4em36ny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mf4em36ny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cachet" /></template>
