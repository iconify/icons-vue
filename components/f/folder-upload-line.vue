<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aqn8xlbnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aqn8xlbnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:folder-upload-line" /></template>
