<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/be0lh-30x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="be0lh-30x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:jump-object-solid" /></template>
