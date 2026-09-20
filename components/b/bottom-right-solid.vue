<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6b6rrbve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="i6b6rrbve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:bottom-right-solid" /></template>
