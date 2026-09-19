<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sb9vtb3ni.css';
import '../../css/s/s9lfmybtd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sb9vtb3ni"/><path class="s9lfmybtd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:checkbox-square" /></template>
