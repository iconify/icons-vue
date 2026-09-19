<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s1gw77--v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s1gw77--v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:file-02" /></template>
