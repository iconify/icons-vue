<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vtc58_b-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="vtc58_b-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:external-link-square-alt" /></template>
