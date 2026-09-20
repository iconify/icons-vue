<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hr-jp9bne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hr-jp9bne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:female-reproductive-system" /></template>
