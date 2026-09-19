<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sp60bbcrp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sp60bbcrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:logo-debian" /></template>
