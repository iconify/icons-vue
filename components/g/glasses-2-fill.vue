<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h12_74eoa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h12_74eoa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:glasses-2-fill" /></template>
