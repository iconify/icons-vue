<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uimoi1b4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="uimoi1b4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:copies-small-filled" /></template>
