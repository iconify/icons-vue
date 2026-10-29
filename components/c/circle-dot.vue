<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yyjo58brx.css';
import '../../css/o/or0-msbfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wm-k yyjo58brx"/><path class="or0-msbfm wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:circle-dot" /></template>
