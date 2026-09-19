<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bg3g5pbsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bg3g5pbsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:code-brackets" /></template>
