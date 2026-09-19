<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7b09gbsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="x7b09gbsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:gamecontroller-alt-fill" /></template>
