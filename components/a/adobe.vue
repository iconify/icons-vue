<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hr_szpbxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":896};
const content = `<path class="hr_szpbxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:adobe" /></template>
