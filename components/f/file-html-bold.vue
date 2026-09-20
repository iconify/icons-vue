<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pwktenbay.css';
import '../../css/o/oxf12mjhy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pwktenbay"/><path class="oxf12mjhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:file-html-bold" /></template>
