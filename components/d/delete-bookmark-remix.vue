<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smmizc_-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="smmizc_-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:delete-bookmark-remix" /></template>
