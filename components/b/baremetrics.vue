<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ie9q1cyqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ie9q1cyqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:baremetrics" /></template>
