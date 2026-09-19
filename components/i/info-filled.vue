<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xiyys2sek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="xiyys2sek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:info-filled" /></template>
