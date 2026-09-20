<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g9-3pccvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="g9-3pccvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:folder-drafts" /></template>
