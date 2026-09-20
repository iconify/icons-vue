<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xx3sd2bgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xx3sd2bgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:folder-check-solid" /></template>
