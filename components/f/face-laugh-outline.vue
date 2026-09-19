<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/prsn6x1ro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="prsn6x1ro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:face-laugh-outline" /></template>
