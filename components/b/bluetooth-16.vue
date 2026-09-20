<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ibylg52rv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ibylg52rv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:bluetooth-16" /></template>
