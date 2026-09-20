<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/brzmvc2-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="brzmvc2-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:folder-with-files-outline" /></template>
