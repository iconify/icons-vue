<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/umrq6t13x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="umrq6t13x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:heading-5" /></template>
