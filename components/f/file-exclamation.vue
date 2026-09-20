<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b8rqb8bcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b8rqb8bcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:file-exclamation" /></template>
