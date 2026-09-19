<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kt03m_jfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="kt03m_jfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:envelope-small" /></template>
