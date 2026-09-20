<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hz3kvt0ck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hz3kvt0ck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:file-onenote-filled" /></template>
