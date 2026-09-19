<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mutex0f_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="mutex0f_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:line-gap-small" /></template>
