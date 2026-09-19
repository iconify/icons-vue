<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2yvml66l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f2yvml66l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:folder-open-solid" /></template>
