<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zurdf3b8r.css';
import '../../css/v/vabm_dihy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zurdf3b8r"/><path clip-rule="evenodd" class="vabm_dihy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:mac-16" /></template>
