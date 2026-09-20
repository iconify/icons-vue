<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b8k7_7bkw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="b8k7_7bkw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:cross" /></template>
