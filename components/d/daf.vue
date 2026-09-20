<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-brzt6qt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-brzt6qt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:daf" /></template>
