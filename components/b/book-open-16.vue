<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tcsx_5noc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="tcsx_5noc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:book-open-16" /></template>
