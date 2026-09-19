<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hq2j_5g3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":470,"height":512};
const content = `<path class="hq2j_5g3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:cnab" /></template>
