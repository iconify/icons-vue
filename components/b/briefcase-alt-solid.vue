<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cybge4bnp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="cybge4bnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:briefcase-alt-solid" /></template>
