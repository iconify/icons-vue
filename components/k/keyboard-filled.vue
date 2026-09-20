<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/byddi6q-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="byddi6q-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:keyboard-filled" /></template>
