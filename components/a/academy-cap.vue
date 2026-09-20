<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5zh32dep.css';
import '../../css/t/t9ceisb5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="j5zh32dep"/><path class="t9ceisb5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:academy-cap" /></template>
