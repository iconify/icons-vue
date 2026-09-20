<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nocrfkt3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nocrfkt3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:envelope-download" /></template>
