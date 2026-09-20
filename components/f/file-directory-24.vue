<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i5y_62azb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i5y_62azb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:file-directory-24" /></template>
