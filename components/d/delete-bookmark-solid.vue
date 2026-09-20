<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/li6xbxbbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="li6xbxbbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:delete-bookmark-solid" /></template>
