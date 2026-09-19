<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yojftwc6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="yojftwc6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:finder-small" /></template>
