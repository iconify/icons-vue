<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/egyn5sb-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="egyn5sb-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:fence-11" /></template>
