<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wdasfzbox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wdasfzbox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:album-covers-filled" /></template>
