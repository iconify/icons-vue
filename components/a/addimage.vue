<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9biptbzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="q9biptbzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:addimage" /></template>
