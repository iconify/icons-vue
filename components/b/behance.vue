<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/trwx034wa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":42,"height":42};
const content = `<path class="trwx034wa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="topcoat:behance" /></template>
