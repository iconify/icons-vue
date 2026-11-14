<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gnei86bvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gnei86bvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:file-x-corner" /></template>
