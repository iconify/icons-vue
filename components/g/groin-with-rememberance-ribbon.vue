<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hrgrmx64i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hrgrmx64i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:groin-with-rememberance-ribbon" /></template>
