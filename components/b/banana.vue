<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv-a9kb-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sv-a9kb-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:banana" /></template>
