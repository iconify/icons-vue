<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d1v1xeb2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d1v1xeb2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:corsair" /></template>
