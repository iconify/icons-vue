<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nb6610bkw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="nb6610bkw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:file-search-solid" /></template>
