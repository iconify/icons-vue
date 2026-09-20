<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7wvzqb7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="c7wvzqb7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:align-left-solid" /></template>
