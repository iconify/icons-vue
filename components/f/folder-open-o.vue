<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/il0b9_6at.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="il0b9_6at"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:folder-open-o" /></template>
