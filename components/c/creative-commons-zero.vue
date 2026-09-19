<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2qj_dbwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="s2qj_dbwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:creative-commons-zero" /></template>
