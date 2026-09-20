<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9xpcnb4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="v9xpcnb4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:facebook-logo-1-remix" /></template>
