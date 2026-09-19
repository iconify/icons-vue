<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a1whhzbbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a1whhzbbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:data-cloud-download-filled" /></template>
