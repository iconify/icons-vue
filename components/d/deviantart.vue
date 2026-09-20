<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bg7z6eq8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bg7z6eq8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:deviantart" /></template>
