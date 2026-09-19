<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1od4ibpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b1od4ibpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:google-drive-warning" /></template>
