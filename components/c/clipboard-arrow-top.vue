<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tsobjn6zc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tsobjn6zc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:clipboard-arrow-top" /></template>
