<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/el2mtsf8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="el2mtsf8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:circle-play" /></template>
