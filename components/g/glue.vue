<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g3qs-bclp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-7,"top":-1.5};
const content = `<path class="g3qs-bclp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:glue" /></template>
