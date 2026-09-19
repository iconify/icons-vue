<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qt_0hdbpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="qt_0hdbpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:erlang" /></template>
