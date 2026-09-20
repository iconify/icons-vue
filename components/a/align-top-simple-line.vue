<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kudbe6bvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kudbe6bvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:align-top-simple-line" /></template>
