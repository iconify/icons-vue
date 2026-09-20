<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/edvt8ugrt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="edvt8ugrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:airtel" /></template>
