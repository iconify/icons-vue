<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zywzn6k9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="zywzn6k9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:file-otf-small-filled" /></template>
