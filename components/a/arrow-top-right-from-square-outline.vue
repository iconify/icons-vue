<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vws14mbpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="vws14mbpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:arrow-top-right-from-square-outline" /></template>
