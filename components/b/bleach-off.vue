<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezekt3baf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ezekt3baf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bleach-off" /></template>
