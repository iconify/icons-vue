<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/om__czbag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="om__czbag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:gift-box-solid" /></template>
