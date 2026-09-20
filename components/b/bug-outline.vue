<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/klfczcboc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="klfczcboc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bug-outline" /></template>
