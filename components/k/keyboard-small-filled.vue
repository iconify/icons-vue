<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/porap235f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="porap235f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:keyboard-small-filled" /></template>
