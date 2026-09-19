<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o0h7pmb9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o0h7pmb9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:creative-commons" /></template>
