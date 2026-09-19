<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o4qrpmb9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o4qrpmb9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:arrow-down" /></template>
