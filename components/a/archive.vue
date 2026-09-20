<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5ucknv3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e5ucknv3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:archive" /></template>
