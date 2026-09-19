<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ruobg3brx.css';
import '../../css/n/nr8lbkbxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ruobg3brx"/><path class="nr8lbkbxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:folder-lock-solid" /></template>
