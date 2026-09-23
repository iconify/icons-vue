<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljr8ztagt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ljr8ztagt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:infinity-duotone" /></template>
