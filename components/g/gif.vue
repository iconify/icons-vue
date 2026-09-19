<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqbrp3biu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jqbrp3biu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:gif" /></template>
