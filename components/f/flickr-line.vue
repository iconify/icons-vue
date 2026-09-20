<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/is7teybgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="is7teybgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:flickr-line" /></template>
