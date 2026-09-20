<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qmjyao5le.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qmjyao5le"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:documents-outline" /></template>
