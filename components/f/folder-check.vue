<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hip0ocbxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="hip0ocbxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:folder-check" /></template>
