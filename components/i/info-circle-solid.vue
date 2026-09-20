<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a9wvh02vu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="a9wvh02vu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:info-circle-solid" /></template>
