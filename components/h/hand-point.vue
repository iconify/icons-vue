<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6e3mnbvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="x6e3mnbvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:hand-point" /></template>
