<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aq-i9lbxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":960,"height":1007};
const content = `<path class="aq-i9lbxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:cube" /></template>
