<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iybqfvbqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="iybqfvbqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:battery-75-16-solid" /></template>
