<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/htso_tk2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="htso_tk2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:hourglass" /></template>
