<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a7zui2bwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a7zui2bwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dumbwhois-dark" /></template>
