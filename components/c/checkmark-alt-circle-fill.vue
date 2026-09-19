<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5-1m4u-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="b5-1m4u-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:checkmark-alt-circle-fill" /></template>
