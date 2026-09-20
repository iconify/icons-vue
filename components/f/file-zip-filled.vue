<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b7kkb9bqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b7kkb9bqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:file-zip-filled" /></template>
