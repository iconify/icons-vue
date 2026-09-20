<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pc6v9sklm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pc6v9sklm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:codesandbox" /></template>
