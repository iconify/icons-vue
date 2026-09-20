<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6f0o2r0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x6f0o2r0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:align-box-center-top" /></template>
