<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e620dkb5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="e620dkb5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:clear-filled" /></template>
