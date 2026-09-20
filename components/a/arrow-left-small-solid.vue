<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_3xcqb6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="c_3xcqb6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:arrow-left-small-solid" /></template>
