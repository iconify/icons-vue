<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t0jif6b6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="t0jif6b6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:align-top-outline" /></template>
