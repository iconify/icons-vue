<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p61rgibvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="p61rgibvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:heading-solid" /></template>
