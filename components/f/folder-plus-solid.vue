<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rf3at3bvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rf3at3bvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:folder-plus-solid" /></template>
