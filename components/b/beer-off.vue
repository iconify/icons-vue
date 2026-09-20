<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ehdcugbfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ehdcugbfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:beer-off" /></template>
