<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nm1seob0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nm1seob0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:file-add" /></template>
