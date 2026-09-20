<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pmju7dxec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pmju7dxec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:comment-x-filled" /></template>
