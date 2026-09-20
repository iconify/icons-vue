<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5d93d0jn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="j5d93d0jn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:jigsaw-details" /></template>
