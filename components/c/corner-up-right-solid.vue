<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fvi4jzfbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fvi4jzfbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:corner-up-right-solid" /></template>
