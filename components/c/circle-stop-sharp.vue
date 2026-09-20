<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/amd21_i0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="amd21_i0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-stop-sharp" /></template>
