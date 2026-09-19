<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fqpak4kov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fqpak4kov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:algolia" /></template>
