<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/saev3jbdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="saev3jbdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:folder-bold" /></template>
