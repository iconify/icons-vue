<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bk5j4gb-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="bk5j4gb-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:circled-information-source-filled" /></template>
