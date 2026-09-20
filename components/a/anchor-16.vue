<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ilbtmozlt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ilbtmozlt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:anchor-16" /></template>
