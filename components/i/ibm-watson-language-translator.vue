<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aesvwbb6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="aesvwbb6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-watson-language-translator" /></template>
