<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b2zphtb3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":498,"height":512};
const content = `<path class="b2zphtb3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:eslint-old" /></template>
