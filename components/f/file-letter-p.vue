<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h938hxb3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="h938hxb3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:file-letter-p" /></template>
