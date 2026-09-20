<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_lrp7rms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r_lrp7rms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:clipboard-text-filled" /></template>
