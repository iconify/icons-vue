<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7z1elnzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z7z1elnzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:browser-solid" /></template>
