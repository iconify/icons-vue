<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ts56i2bjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ts56i2bjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:grin-beam-sweat-solid" /></template>
