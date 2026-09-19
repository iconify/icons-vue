<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ao-aiub9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="ao-aiub9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:dosbox" /></template>
