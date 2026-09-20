<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gu5e9zo7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gu5e9zo7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:case-sensitive-fill" /></template>
