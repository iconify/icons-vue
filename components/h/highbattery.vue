<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c67e4e7nl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="c67e4e7nl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:highbattery" /></template>
