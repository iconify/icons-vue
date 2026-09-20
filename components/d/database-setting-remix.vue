<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bqxmsm42o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="bqxmsm42o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:database-setting-remix" /></template>
