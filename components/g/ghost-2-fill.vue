<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bq8psnb7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bq8psnb7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:ghost-2-fill" /></template>
