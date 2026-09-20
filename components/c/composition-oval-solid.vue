<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aeb5a4lfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="aeb5a4lfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:composition-oval-solid" /></template>
