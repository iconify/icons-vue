<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kk8t634uh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="kk8t634uh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:backup" /></template>
