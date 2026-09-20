<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mk-59o6jn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="mk-59o6jn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:chevron-up" /></template>
