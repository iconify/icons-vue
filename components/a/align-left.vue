<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rp4rjm96f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-5,"top":-7};
const content = `<path class="rp4rjm96f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:align-left" /></template>
