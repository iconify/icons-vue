<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cdof_xbaa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cdof_xbaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:file-empty-02" /></template>
