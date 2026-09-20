<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gmt3k8bda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gmt3k8bda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:headphones2" /></template>
