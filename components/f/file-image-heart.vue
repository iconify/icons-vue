<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h0zvav3hn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h0zvav3hn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:file-image-heart" /></template>
