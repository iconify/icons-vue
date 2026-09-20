<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zwkw435-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zwkw435-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:doc-expand" /></template>
