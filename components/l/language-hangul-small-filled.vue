<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wp1bg9iuc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="wp1bg9iuc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:language-hangul-small-filled" /></template>
