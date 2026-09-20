<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m7ay1achv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m7ay1achv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:flickr" /></template>
