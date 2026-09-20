<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bcqlkersn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="bcqlkersn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:khanda-on-square" /></template>
