<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghwau-10a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ghwau-10a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:aurelia" /></template>
