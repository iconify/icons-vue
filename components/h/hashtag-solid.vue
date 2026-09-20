<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i7658vijs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="i7658vijs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:hashtag-solid" /></template>
