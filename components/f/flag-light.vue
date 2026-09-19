<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3kpty1jk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s3kpty1jk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:flag-light" /></template>
