<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jpmw0obfn.css';
import '../../css/e/ehafz-rwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jpmw0obfn"/><path class="ehafz-rwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:information-filled" /></template>
