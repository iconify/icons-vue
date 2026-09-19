<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bpt2b0b1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bpt2b0b1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:heart-solid" /></template>
