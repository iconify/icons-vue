<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ob0xyledb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="ob0xyledb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:inspection" /></template>
