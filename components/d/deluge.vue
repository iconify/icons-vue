<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yv55pk_2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yv55pk_2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:deluge" /></template>
