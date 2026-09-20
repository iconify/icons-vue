<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2wa24beh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="i2wa24beh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:hand-open" /></template>
