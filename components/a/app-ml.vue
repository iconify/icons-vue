<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e64vo7e9t.css';
import '../../css/i/iste4e9kh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="e64vo7e9t ouiIcon__fillSecondary"/><path class="iste4e9kh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:app-ml" /></template>
