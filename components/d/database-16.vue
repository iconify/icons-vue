<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h14_rhpgn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="h14_rhpgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:database-16" /></template>
