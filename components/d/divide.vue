<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/to5trbc1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="to5trbc1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:divide" /></template>
