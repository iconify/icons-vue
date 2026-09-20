<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w3bvj6h0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w3bvj6h0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:folder-connect-filled" /></template>
