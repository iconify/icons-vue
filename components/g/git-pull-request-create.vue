<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l8an-u_vy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l8an-u_vy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:git-pull-request-create" /></template>
