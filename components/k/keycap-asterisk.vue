<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0hwpkaar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="b0hwpkaar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:keycap-asterisk" /></template>
