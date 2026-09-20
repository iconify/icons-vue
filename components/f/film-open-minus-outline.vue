<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sgyf-zbar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sgyf-zbar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:film-open-minus-outline" /></template>
