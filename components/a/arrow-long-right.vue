<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2wo5_mds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f2wo5_mds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-long-right" /></template>
