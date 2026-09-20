<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqrwg2b1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jqrwg2b1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:folder-open-filled" /></template>
