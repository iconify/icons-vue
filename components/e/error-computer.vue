<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/li8w93b-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="li8w93b-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:error-computer" /></template>
