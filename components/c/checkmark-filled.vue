<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fqeftx7zl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="fqeftx7zl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:checkmark-filled" /></template>
