<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oh0km5biw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="oh0km5biw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:cloud-filled" /></template>
