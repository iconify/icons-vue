<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ho9pqgbqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ho9pqgbqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:booklore-light" /></template>
