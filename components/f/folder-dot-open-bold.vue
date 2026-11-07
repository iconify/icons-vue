<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yw7lxg0ts.css';
import '../../css/n/n7p431bil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yw7lxg0ts"/><path class="n7p431bil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:folder-dot-open-bold" /></template>
