<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aexgi1bnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":717,"height":718};
const content = `<path class="aexgi1bnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:ban" /></template>
