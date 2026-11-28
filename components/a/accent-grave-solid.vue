<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhx9fhbmx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yhx9fhbmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:accent-grave-solid" /></template>
