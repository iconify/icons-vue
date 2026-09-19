<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vp49s3s_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vp49s3s_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:folder" /></template>
