<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/js-u0nt0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="js-u0nt0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:briefcase-dollar-solid" /></template>
