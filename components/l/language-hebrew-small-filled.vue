<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jo0vp2bog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="jo0vp2bog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:language-hebrew-small-filled" /></template>
