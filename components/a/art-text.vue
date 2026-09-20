<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ehra4u3qy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ehra4u3qy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:art-text" /></template>
