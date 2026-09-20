<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r20zsnx-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r20zsnx-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:dogecoin" /></template>
