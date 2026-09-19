<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/or7pjbbqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="or7pjbbqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:champagne-glasses-solid" /></template>
