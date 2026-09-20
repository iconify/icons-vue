<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sf_w8fb2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sf_w8fb2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:cassette" /></template>
