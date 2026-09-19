<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rah705b0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="rah705b0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:email-fill-12" /></template>
