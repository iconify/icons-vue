<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ono7gqb3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ono7gqb3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:grid-3x2-sharp" /></template>
