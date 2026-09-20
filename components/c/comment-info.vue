<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gawx2ac1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gawx2ac1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:comment-info" /></template>
