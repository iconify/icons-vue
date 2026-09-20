<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gwmyw5b7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gwmyw5b7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:hard-drive-fill" /></template>
