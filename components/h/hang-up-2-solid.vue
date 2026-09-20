<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdew_8bek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="bdew_8bek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:hang-up-2-solid" /></template>
