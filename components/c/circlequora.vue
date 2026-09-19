<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zat6rqfwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="zat6rqfwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:circlequora" /></template>
