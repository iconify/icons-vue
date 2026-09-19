<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p6moad0xy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="p6moad0xy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:closed-book-filled" /></template>
