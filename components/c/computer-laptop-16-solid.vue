<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/idhstyjou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="idhstyjou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:computer-laptop-16-solid" /></template>
