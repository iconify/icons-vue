<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ocku_jbwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ocku_jbwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:clubs-symbol-solid" /></template>
