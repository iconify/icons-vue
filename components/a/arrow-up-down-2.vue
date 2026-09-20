<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xd_kjk6cf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xd_kjk6cf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:arrow-up-down-2" /></template>
