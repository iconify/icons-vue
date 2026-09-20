<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o5lk7tbdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="o5lk7tbdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:dropbox-flat" /></template>
