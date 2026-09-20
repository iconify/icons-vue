<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e24y9nbby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":16};
const content = `<path class="e24y9nbby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:bell" /></template>
