<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvqwjdbok.css';
import '../../css/f/fb99aacni.css';
import '../../css/c/c-5-uyb3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nvqwjdbok"/><path class="fb99aacni"/><path class="c-5-uyb3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cherry-picker-48" /></template>
