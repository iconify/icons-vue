<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pdqpw2bic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pdqpw2bic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:folder-cloud-filled" /></template>
