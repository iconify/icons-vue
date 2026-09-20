<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vo8j22c4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vo8j22c4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-dropbox" /></template>
