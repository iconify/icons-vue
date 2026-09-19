<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o6xqsjb9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="o6xqsjb9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:igloo" /></template>
