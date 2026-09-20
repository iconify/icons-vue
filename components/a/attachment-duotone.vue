<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sm0y7t7oq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sm0y7t7oq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:attachment-duotone" /></template>
