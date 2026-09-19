<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jmn3w7obp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":305,"height":512};
const content = `<path class="jmn3w7obp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:leiningen" /></template>
