<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m7t3zob6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":575,"height":512};
const content = `<path class="m7t3zob6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:apl-old" /></template>
