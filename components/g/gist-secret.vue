<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hpz_xxn6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":16};
const content = `<path class="hpz_xxn6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:gist-secret" /></template>
