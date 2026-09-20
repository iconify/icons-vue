<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lm9ywsb4k.css';
import '../../css/n/ntb6s4b4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lm9ywsb4k"/><path class="ntb6s4b4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:clipboard-user" /></template>
