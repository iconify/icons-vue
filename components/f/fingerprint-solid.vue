<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/okwql1bgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="okwql1bgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:fingerprint-solid" /></template>
