<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/asn7qebaa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="asn7qebaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:emirates" /></template>
