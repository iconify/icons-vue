<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ms8vhaccy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ms8vhaccy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:arrow-up-right-down-left-solid" /></template>
