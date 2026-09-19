<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/siist1o2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="siist1o2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:drumstick-bite-solid" /></template>
