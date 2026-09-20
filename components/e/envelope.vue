<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9iirbbwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":896};
const content = `<path class="k9iirbbwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:envelope" /></template>
