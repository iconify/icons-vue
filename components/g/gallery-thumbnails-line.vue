<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ain8fqvmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ain8fqvmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:gallery-thumbnails-line" /></template>
