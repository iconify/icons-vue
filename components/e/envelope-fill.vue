<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fvuhvccgn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fvuhvccgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:envelope-fill" /></template>
