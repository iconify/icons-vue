<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q74fwu1qf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary q74fwu1qf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:git-branch-duotone" /></template>
