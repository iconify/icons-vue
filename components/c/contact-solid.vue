<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hkc4x7rmc.css';
import '../../css/j/j5ymz25ec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="hkc4x7rmc"/><path class="j5ymz25ec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:contact-solid" /></template>
