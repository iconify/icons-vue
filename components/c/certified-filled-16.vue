<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tlfswok4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="tlfswok4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:certified-filled-16" /></template>
