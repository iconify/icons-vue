<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/silp9ount.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="silp9ount"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:globe-off" /></template>
