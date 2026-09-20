<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9oa3ab1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k9oa3ab1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:folder-link-filled" /></template>
