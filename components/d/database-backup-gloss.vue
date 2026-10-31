<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hf5x55bnt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hf5x55bnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:database-backup-gloss" /></template>
