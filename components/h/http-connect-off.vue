<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2wdr2ceg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c2wdr2ceg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:http-connect-off" /></template>
