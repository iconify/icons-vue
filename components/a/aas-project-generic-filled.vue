<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ou-hkcell.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ou-hkcell"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:aas-project-generic-filled" /></template>
