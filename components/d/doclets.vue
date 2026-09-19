<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ua6_9pbeu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ua6_9pbeu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:doclets" /></template>
