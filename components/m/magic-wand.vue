<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xs47fsy6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xs47fsy6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:magic-wand" /></template>
