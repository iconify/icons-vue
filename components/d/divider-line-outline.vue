<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aowkw-b5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="aowkw-b5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:divider-line-outline" /></template>
