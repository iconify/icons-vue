<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjl44flrt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cjl44flrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:copy-light" /></template>
