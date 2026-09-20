<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aclqr6c9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aclqr6c9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:group-2-line" /></template>
