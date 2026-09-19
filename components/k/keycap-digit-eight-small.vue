<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s03suobts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="s03suobts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:keycap-digit-eight-small" /></template>
