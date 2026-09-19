<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f7756kbvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="f7756kbvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:capsule-fill" /></template>
