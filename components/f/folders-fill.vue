<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ie1qbx9oa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ie1qbx9oa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:folders-fill" /></template>
