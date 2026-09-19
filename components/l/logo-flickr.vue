<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fx39xbeov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fx39xbeov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:logo-flickr" /></template>
