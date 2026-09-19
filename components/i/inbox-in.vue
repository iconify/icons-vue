<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bke2m3a2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bke2m3a2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:inbox-in" /></template>
