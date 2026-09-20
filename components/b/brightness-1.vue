<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/afkg_7yto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="afkg_7yto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:brightness-1" /></template>
