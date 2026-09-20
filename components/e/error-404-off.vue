<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eag81cn8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eag81cn8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:error-404-off" /></template>
