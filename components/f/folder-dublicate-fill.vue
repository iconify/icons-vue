<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vgfbc-ifb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vgfbc-ifb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:folder-dublicate-fill" /></template>
