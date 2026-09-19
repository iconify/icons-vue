<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ckx81ibjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":768};
const content = `<path class="ckx81ibjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:counter" /></template>
