<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bp6xqgbqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bp6xqgbqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kohls-dark" /></template>
