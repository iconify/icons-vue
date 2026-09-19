<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iizhlp7_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iizhlp7_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:arrow-down-left" /></template>
