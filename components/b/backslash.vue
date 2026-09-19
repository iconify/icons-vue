<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c0c_zi20n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":559,"height":854};
const content = `<path class="c0c_zi20n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:backslash" /></template>
