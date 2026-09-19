<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b3j61h5fu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="b3j61h5fu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:indent-more" /></template>
