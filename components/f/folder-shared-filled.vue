<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqah0fdbt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jqah0fdbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:folder-shared-filled" /></template>
