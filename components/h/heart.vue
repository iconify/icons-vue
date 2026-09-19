<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/btphczb_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="btphczb_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:heart" /></template>
