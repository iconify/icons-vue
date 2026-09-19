<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e0wxxkbbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e0wxxkbbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:alloy" /></template>
