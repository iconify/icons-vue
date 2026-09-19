<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/obm7hd71g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="obm7hd71g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:keycap-digit-zero-small" /></template>
