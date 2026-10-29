<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/apgew5uau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="apgew5uau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:anchor-solid" /></template>
