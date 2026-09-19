<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fpgdgjb3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":448};
const content = `<path class="fpgdgjb3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:asterisk" /></template>
