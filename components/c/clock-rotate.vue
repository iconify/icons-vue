<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-wnu-1im.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d-wnu-1im"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:clock-rotate" /></template>
