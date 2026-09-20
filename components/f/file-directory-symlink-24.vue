<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/auljhabfb.css';
import '../../css/z/zqdkcibks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="auljhabfb"/><path class="zqdkcibks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:file-directory-symlink-24" /></template>
