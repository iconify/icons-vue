<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4f9lhb6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="z4f9lhb6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:briefcase-fill" /></template>
