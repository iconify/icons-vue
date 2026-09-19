<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ldfomccsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1025};
const content = `<path class="ldfomccsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:clock" /></template>
