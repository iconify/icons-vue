<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f7k1ti8-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f7k1ti8-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:loader-circle-solid" /></template>
