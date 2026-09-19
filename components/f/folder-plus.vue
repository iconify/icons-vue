<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n6at7ccmr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n6at7ccmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:folder-plus" /></template>
