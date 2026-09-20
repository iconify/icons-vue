<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cb_59lfpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="cb_59lfpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:double-caret-left-solid" /></template>
