<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nowda5nca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nowda5nca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:diamond-02" /></template>
