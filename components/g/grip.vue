<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wtpfblb0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="wtpfblb0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:grip" /></template>
