<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8dohpt2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="x8dohpt2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:chevron-double-up-fill-12" /></template>
