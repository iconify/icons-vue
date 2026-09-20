<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x03bb4t8g.css';
import '../../css/k/k-_e98l6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<rect class="x03bb4t8g"/><path class="k-_e98l6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:adobe-illustrator" /></template>
