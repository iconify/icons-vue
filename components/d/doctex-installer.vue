<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hbvmo8dlf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hbvmo8dlf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:doctex-installer" /></template>
