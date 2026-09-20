<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sdvf5flpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sdvf5flpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:checkbox-filled" /></template>
