<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sz-mjg0wu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="sz-mjg0wu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:grid" /></template>
