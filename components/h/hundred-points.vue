<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/enll67bjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path clip-rule="evenodd" class="enll67bjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:hundred-points" /></template>
