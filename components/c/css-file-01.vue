<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sbcwffbuf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sbcwffbuf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:css-file-01" /></template>
