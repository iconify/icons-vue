<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bul0zbb0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="bul0zbb0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:database-setting-solid" /></template>
