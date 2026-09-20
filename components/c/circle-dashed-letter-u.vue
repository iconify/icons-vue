<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aluz32qjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aluz32qjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-dashed-letter-u" /></template>
