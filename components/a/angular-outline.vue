<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r5c806b7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="r5c806b7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:angular-outline" /></template>
