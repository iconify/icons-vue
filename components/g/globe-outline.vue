<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/znezuzb6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="znezuzb6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:globe-outline" /></template>
