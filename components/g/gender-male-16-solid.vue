<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ax6hn1byu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ax6hn1byu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:gender-male-16-solid" /></template>
