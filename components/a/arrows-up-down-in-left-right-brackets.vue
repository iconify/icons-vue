<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dmd7zetxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="dmd7zetxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:arrows-up-down-in-left-right-brackets" /></template>
