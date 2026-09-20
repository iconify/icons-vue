<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oe5qejdtc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":182,"height":218};
const content = `<path class="oe5qejdtc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:bitwarden" /></template>
