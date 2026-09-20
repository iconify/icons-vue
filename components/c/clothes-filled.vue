<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smmc-ljxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="smmc-ljxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:clothes-filled" /></template>
