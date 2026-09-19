<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/atay87bmr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":352,"height":512};
const content = `<path class="atay87bmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:label" /></template>
