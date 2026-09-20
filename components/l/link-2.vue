<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mnuezh7xd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mnuezh7xd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:link-2" /></template>
