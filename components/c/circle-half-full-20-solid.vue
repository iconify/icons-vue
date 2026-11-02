<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qrh45udrk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="qrh45udrk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:circle-half-full-20-solid" /></template>
