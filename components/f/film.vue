<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/agdrazf8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="agdrazf8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:film" /></template>
