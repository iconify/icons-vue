<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udfnkbb0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1026,"height":1026};
const content = `<path class="udfnkbb0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:flower" /></template>
