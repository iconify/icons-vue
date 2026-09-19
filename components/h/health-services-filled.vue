<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hd6fsacyv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hd6fsacyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:health-services-filled" /></template>
