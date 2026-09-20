<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a5ookx5_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-1.5,"top":-4};
const content = `<path class="a5ookx5_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:layers-f" /></template>
