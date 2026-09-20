<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/soaeigb4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-6.5,"top":-6.5};
const content = `<path class="soaeigb4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:clear-format" /></template>
