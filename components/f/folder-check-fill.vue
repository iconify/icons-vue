<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vnmvchc5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vnmvchc5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:folder-check-fill" /></template>
