<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b22ju_bpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="b22ju_bpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:delicious" /></template>
