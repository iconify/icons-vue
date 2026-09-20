<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hcre68axd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hcre68axd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:check-list-filled" /></template>
