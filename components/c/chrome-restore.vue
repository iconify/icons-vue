<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gt8sy1bpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gt8sy1bpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:chrome-restore" /></template>
