<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oc9wkibkf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="oc9wkibkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:forward-end-alt-fill" /></template>
