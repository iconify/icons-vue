<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ozz-8wjpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path clip-rule="evenodd" class="ozz-8wjpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:linear-wordmark" /></template>
