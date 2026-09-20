<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rebt0moqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rebt0moqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:edit-pen" /></template>
