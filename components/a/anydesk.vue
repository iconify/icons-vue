<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wf3d_3bxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wf3d_3bxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:anydesk" /></template>
