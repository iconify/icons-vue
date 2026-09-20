<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/en6b4kiau.css';
import '../../css/e/e7ebmvq0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="en6b4kiau"/><path class="e7ebmvq0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:globe-timezone-duotone" /></template>
