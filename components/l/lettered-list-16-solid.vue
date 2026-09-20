<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jr102vbje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jr102vbje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:lettered-list-16-solid" /></template>
