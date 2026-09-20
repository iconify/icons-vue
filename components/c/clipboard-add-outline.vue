<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uogvzbc0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uogvzbc0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:clipboard-add-outline" /></template>
