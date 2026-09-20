<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oswrj__up.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="oswrj__up"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:bug-virus-folder-solid" /></template>
