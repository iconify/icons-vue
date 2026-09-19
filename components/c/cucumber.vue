<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lp2zqlb5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":435,"height":512};
const content = `<path clip-rule="evenodd" class="lp2zqlb5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:cucumber" /></template>
