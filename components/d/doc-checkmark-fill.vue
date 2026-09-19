<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9p45cb5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="k9p45cb5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:doc-checkmark-fill" /></template>
