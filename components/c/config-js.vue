<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1pj_126s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b1pj_126s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:config-js" /></template>
