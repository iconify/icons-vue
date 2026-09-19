<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g973qacms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="g973qacms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:leaf-fill-12" /></template>
