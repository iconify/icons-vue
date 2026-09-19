<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pb7rgwp0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pb7rgwp0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:archive-box-x-mark" /></template>
