<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m6km1gb0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m6km1gb0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:camera-slash" /></template>
