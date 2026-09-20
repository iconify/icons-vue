<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/puyvk7u7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="puyvk7u7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:book" /></template>
