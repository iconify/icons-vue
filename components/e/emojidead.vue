<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f7e7i6bll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="f7e7i6bll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:emojidead" /></template>
