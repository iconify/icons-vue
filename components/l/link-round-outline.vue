<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmrlyvb5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kmrlyvb5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:link-round-outline" /></template>
