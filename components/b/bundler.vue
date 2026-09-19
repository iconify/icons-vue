<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yo0ocib5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":481,"height":512};
const content = `<path class="yo0ocib5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:bundler" /></template>
