<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pa9u3uthd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="pa9u3uthd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:diagram" /></template>
